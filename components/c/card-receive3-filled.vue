<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0g1x7baf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0g1x7baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:card-receive3-filled" /></template>
