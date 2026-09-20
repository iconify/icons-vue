<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz1qw1t2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1qw1t2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-edit-alt-1-fill" /></template>
