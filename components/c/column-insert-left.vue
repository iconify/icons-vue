<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4pqvcl0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4pqvcl0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:column-insert-left" /></template>
