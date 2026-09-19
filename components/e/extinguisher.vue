<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lwi2rjbdb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":352,"height":520};
const content = `<path class="lwi2rjbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:extinguisher" /></template>
