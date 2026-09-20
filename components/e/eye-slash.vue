<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kq6n_s_po.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kq6n_s_po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:eye-slash" /></template>
