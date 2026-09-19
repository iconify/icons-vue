<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzi00bpt.css';
import '../../css/l/lml2oc9mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="lml2oc9mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:chevron-up-square" /></template>
