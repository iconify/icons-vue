<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbhg10sxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bbhg10sxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kopia" /></template>
