<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkhmj7e-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkhmj7e-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:archive-box-arrow-up-solid" /></template>
