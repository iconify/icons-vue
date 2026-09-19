<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bh-g3b15f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bh-g3b15f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:citroen" /></template>
