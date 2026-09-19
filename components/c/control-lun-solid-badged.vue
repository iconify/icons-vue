<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu410db3i.css';
import '../../css/v/voo8clboo.css';
import '../../css/l/lmf0ecbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="mu410db3i"/><path class="voo8clboo"/><circle class="lmf0ecbhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:control-lun-solid-badged" /></template>
