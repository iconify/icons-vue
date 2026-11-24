<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as5f_obem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as5f_obem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-filled" /></template>
