<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to9jqqqje.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="to9jqqqje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bag-check-outline" /></template>
