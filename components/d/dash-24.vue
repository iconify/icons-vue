<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plk7a033w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="plk7a033w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dash-24" /></template>
