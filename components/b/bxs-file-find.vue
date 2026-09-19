<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1si9h-km.css';
import '../../css/b/buc-_ybgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1si9h-km"/><circle class="buc-_ybgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-file-find" /></template>
