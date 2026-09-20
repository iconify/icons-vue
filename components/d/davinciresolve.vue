<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7nmlpbiv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7nmlpbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:davinciresolve" /></template>
