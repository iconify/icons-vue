<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktyj-1b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktyj-1b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:long-up-right" /></template>
