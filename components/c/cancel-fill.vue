<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q40v_abfh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q40v_abfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:cancel-fill" /></template>
