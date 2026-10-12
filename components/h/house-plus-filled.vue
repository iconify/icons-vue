<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y53soubyt.css';
import '../../css/o/o604fd26w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y53soubyt"/><path class="o604fd26w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-plus-filled" /></template>
