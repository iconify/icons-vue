<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1r-r1ukc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c1r-r1ukc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:badge-alert-filled" /></template>
