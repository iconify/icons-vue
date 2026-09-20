<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sa55slbvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sa55slbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:halloween-candy-bold" /></template>
