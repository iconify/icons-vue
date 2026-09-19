<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/juoi7tb-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="juoi7tb-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:database-outlined" /></template>
