<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkd5oxl6c.css';
import '../../css/b/bc_ody0we.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="fkd5oxl6c"/><path class="bc_ody0we"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:arrow-circle-right-o" /></template>
