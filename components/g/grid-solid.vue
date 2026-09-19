<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ky9lh9bsn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ky9lh9bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:grid-solid" /></template>
