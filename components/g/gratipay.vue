<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfubp8nmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="dfubp8nmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:gratipay" /></template>
