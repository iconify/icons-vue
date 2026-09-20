<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtqsoabtw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gtqsoabtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-list-outline" /></template>
