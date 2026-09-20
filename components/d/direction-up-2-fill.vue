<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jbml36fwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbml36fwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-up-2-fill" /></template>
