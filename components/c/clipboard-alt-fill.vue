<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a7k9mhc2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7k9mhc2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:clipboard-alt-fill" /></template>
