<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvz4neb7i.css';
import '../../css/o/o-xvump-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zvz4neb7i"/><path class="o-xvump-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fusionauth" /></template>
