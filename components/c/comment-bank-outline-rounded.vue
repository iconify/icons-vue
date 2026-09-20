<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c907gxbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-bank-outline-rounded" /></template>
<style>
.c907gxbou {
  fill: currentColor;
  d: path("m6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.616 3h14.769q.69 0 1.153.463T21 4.616v10.769q0 .69-.462 1.153T19.385 17zm13.308-1q.23 0 .423-.192t.192-.423V4.615q0-.23-.192-.423T19.385 4h-2v5.414q0 .242-.202.36t-.414-.012l-1.086-.653q-.142-.086-.298-.086t-.298.087L14 9.762q-.212.13-.413.012t-.202-.36V4h-8.77q-.23 0-.423.192T4 4.615v13.03L5.65 16zM4 16V4v13.385z");
}

</style>
