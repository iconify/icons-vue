<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tn2r_k_3k.css';
import '../../css/t/tng0ocbay.css';
import '../../css/w/wk855qbpc.css';
import '../../css/c/csbi0o7qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":11};
const content = `<circle class="tn2r_k_3k"/><circle class="tng0ocbay"/><circle class="wk855qbpc"/><path class="csbi0o7qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:list" /></template>
