<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m747jmphf.css';
import '../../css/x/xvqdfg4fc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m747jmphf"/><path class="xvqdfg4fc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:check-shield" /></template>
