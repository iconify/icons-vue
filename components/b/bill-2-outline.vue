<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/htqdaxb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htqdaxb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-2-outline" /></template>
