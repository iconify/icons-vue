<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwzpgobru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="uwzpgobru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-delete-bin-5-remove-delete-empty-bin-trash-garbage" /></template>
