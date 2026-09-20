<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x1rkvo-db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x1rkvo-db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:limesurvey-light" /></template>
