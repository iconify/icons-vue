<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9mr-b15w.css';
import '../../css/e/ewvinnbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9mr-b15w"/><path class="ewvinnbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:credit-card-24" /></template>
