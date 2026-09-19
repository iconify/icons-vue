<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekh-ymbqu.css';
import '../../css/k/k27hiquiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekh-ymbqu"/><path class="k27hiquiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:duplicate-sharp" /></template>
