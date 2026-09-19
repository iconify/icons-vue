<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd-_1dbee.css';
import '../../css/b/b9s2v5y7q.css';
import '../../css/p/pvjzk9b8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qd-_1dbee"/><path class="b9s2v5y7q"/><path class="pvjzk9b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:cloth" /></template>
