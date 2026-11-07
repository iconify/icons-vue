<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb4o__b5r.css';
import '../../css/n/n2zpnybfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb4o__b5r"/><path clip-rule="evenodd" class="n2zpnybfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:double-alt-arrow-left-bold-duotone" /></template>
