<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufey87b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ufey87b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:limesurvey" /></template>
