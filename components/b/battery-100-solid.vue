<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nuxb7lb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nuxb7lb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:battery-100-solid" /></template>
