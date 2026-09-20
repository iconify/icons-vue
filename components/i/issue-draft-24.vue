<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myo5-e-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myo5-e-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:issue-draft-24" /></template>
