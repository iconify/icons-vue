<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/momz31b0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="momz31b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:documents" /></template>
