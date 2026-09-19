<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z13c673tt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z13c673tt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:flag-alt-2-filled" /></template>
