<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-1flr4c.css';
import '../../css/b/buc-_ybgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-1flr4c"/><circle class="buc-_ybgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:file-find" /></template>
