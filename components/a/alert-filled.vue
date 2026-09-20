<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr5f0eiog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kr5f0eiog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:alert-filled" /></template>
