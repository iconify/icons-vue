<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwu26er0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mwu26er0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:briefcase-solid" /></template>
