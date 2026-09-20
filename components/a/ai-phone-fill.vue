<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku6a4achx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku6a4achx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-phone-fill" /></template>
