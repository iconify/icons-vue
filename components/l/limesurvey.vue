<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlmdd61jd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlmdd61jd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:limesurvey" /></template>
