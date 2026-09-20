<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ef9db-k.css';
import '../../css/o/odnck4blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j5ef9db-k"/><path class="odnck4blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:generate-content" /></template>
