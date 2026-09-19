<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3se7-35b.css';
import '../../css/d/dkh-5rbja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3se7-35b"/><path class="dkh-5rbja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:cloud-rain" /></template>
