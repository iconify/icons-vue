<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/a4gyq6a4f.css';
import '../../css/o/oyi6v4b7q.css';
import '../../css/s/s78kz7brn.css';
import '../../css/c/c_bjunb0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a4gyq6a4f"/><path class="oyi6v4b7q"/><path class="s78kz7brn"/><path class="c_bjunb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:fence-duotone" /></template>
