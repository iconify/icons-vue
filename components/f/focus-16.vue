<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwlcgjbwv.css';
import '../../css/d/dngedb3dc.css';
import '../../css/l/lg-e2pb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="dwlcgjbwv"/><path clip-rule="evenodd" class="dngedb3dc"/><path class="lg-e2pb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:focus-16" /></template>
