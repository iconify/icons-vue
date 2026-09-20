<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7azwk40j.css';
import '../../css/z/zx-jj4ivt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7azwk40j"/><path class="zx-jj4ivt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:conv" /></template>
