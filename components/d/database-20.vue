<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_na6f67p.css';
import '../../css/b/ba7omlb3c.css';
import '../../css/a/apo2ptbjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d_na6f67p"/><path class="ba7omlb3c"/><path class="apo2ptbjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:database-20" /></template>
