<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s06hljcsa.css';
import '../../css/b/b4hqx5wjx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s06hljcsa"/><path class="b4hqx5wjx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adnanh-webhook" /></template>
