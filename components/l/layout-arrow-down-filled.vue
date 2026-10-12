<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdwx88n2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdwx88n2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:layout-arrow-down-filled" /></template>
