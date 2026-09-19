<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amvdw8b4x.css';
import '../../css/o/om9xhncdy.css';
import '../../css/h/h-ythmv4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amvdw8b4x"/><path class="om9xhncdy"/><path class="h-ythmv4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-europe" /></template>
