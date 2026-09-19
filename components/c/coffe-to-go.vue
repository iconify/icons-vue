<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgx0dlr5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgx0dlr5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:coffe-to-go" /></template>
