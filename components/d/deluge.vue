<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5m15vbeq.css';
import '../../css/z/z16bp5rql.css';
import '../../css/s/smgw8kb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5m15vbeq"/><path class="z16bp5rql"/><path class="smgw8kb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deluge" /></template>
