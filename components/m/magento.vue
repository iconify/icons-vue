<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jab7xhb0n.css';
import '../../css/v/vla3-w5tf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jab7xhb0n"/><path class="vla3-w5tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:magento" /></template>
