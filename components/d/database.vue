<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nixdnt-qy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nixdnt-qy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:database" /></template>
