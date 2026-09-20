<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugst-xypg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugst-xypg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bell" /></template>
