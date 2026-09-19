<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/l6kxnt1jd.css';
import '../../css/o/owtansbof.css';
import '../../css/q/qo6s3bcoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="l6kxnt1jd"/><path class="owtansbof"/><path class="qo6s3bcoz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:crab" /></template>
