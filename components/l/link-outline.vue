<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luwxsnbji.css';
import '../../css/p/pqfht_-da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luwxsnbji"/><path class="pqfht_-da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:link-outline" /></template>
