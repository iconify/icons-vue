<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfv-qnbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:decorator" /></template>
<style>
.tfv-qnbrt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.125 2.25h5.75q2.848 0 4.861 2.014t2.014 4.861v5.75q0 2.848-2.014 4.861t-4.861 2.014h-5.75q-2.848 0-4.861-2.014T2.25 14.875v-5.75q0-2.848 2.014-4.861T9.125 2.25m3.924 3.954q-1.048-.552-2.096 0l-3.251 1.71q-.282.149-.497.337q-.097.006-.189.037q-.091.03-.172.082t-.147.124q-.065.071-.11.157q-.039.075-.061.158q-.022.082-.025.168q-.002.085.014.169q.017.084.052.162q-.066.279-.066.598v4.188q-.001 1.358 1.202 1.992l3.249 1.71q.241.126.482.195q.107.123.255.191t.312.068t.312-.068t.255-.191q.241-.069.481-.195l3.251-1.71q1.202-.634 1.201-1.992V9.906q0-.319-.066-.598q.035-.078.052-.162t.014-.169t-.025-.168t-.061-.158q-.045-.086-.11-.157q-.066-.071-.147-.124q-.081-.052-.173-.082t-.188-.037q-.216-.188-.498-.337z");
}

</style>
