<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w710m_idj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w710m_idj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:cancel" /></template>
