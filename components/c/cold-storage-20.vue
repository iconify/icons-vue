<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyvjvhb1l.css';
import '../../css/z/zrqlkvb4c.css';
import '../../css/o/oov7epbkt.css';
import '../../css/h/hh-vtxt5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zyvjvhb1l"/><path class="zrqlkvb4c"/><path class="oov7epbkt"/><path class="hh-vtxt5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cold-storage-20" /></template>
