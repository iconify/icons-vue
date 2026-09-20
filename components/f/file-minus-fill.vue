<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9db1acos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9db1acos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-minus-fill" /></template>
