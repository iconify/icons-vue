<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9vc9hb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a9vc9hb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:limesurvey-dark" /></template>
