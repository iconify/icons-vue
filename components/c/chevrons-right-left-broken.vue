<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/k65hgkb4u.css';
import '../../css/g/gsvz4o5yr.css';
import '../../css/l/lq7l02bvw.css';
import '../../css/d/d15wbrb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k65hgkb4u"/><path class="gsvz4o5yr"/><path class="lq7l02bvw"/><path class="d15wbrb2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chevrons-right-left-broken" /></template>
