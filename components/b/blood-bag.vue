<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho23q-kec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ho23q-kec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:blood-bag" /></template>
