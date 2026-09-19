<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h66-yoa9l.css';
import '../../css/w/w-bvnpfvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="h66-yoa9l"/><path class="w-bvnpfvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:group-outlined" /></template>
