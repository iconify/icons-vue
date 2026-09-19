<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2u665ban.css';
import '../../css/b/bil7h4hxb.css';
import '../../css/k/k0v0v9boq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="k2u665ban"><path class="bil7h4hxb"/><path clip-rule="evenodd" class="k0v0v9boq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:mail-out-solid" /></template>
