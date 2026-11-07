<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxodcsbxg.css';
import '../../css/b/bioritexk.css';
import '../../css/h/hmpjhub9l.css';
import '../../css/p/pzmtr-buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxodcsbxg"/><path class="bioritexk"/><path class="hmpjhub9l"/><path clip-rule="evenodd" class="pzmtr-buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-kanban-outline" /></template>
