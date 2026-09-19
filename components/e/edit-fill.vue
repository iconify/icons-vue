<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xa4k5mg7o.css';
import '../../css/z/za5m-1b2a.css';
import '../../css/b/b_zs5hbah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xa4k5mg7o"/><path class="za5m-1b2a"/><path class="b_zs5hbah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:edit-fill" /></template>
