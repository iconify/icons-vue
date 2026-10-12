<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exe5mchjt.css';
import '../../css/f/f4f8fe34r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exe5mchjt"/><path class="f4f8fe34r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:database-arrow-down-filled" /></template>
