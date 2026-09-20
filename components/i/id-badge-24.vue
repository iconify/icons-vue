<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu8rqjbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu8rqjbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:id-badge-24" /></template>
