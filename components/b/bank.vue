<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-e6xd29v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="q-e6xd29v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:bank" /></template>
