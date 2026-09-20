<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp3sgac-k.css';
import '../../css/y/yja7dnbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp3sgac-k"/><path class="yja7dnbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:gel" /></template>
