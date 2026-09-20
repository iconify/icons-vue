<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpqb6fb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gpqb6fb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:inbox-outline" /></template>
