<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zit9a7yxo.css';
import '../../css/b/br0wqld1w.css';
import '../../css/h/hqpwl64dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zit9a7yxo"/><path class="br0wqld1w"/><path clip-rule="evenodd" class="hqpwl64dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:fridge-outline" /></template>
