<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwzj-8bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uwzj-8bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:exclamation-triangle" /></template>
