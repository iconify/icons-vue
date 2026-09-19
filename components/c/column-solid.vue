<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce_od5b1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ce_od5b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:column-solid" /></template>
