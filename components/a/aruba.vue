<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k7p2enbbo.css';
import '../../css/v/v1a49acba.css';
import '../../css/t/tkrg51qty.css';
import '../../css/e/ewv-anbkb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="k7p2enbbo"/><path class="v1a49acba"/><path class="tkrg51qty"/><path class="ewv-anbkb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:aruba" /></template>
