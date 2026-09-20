<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2c1bbqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_2c1bbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:check-double" /></template>
