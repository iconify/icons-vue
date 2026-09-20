<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f9h2uzlmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:docs-outline-rounded" /></template>
<style>
.f9h2uzlmg {
  fill: currentColor;
  d: path("M7.616 21q-.691 0-1.153-.462T6 19.385V4.615q0-.69.463-1.152T7.616 3h5.367q.323 0 .628.121t.522.358l3.408 3.523q.217.217.338.503t.121.609v11.27q0 .691-.462 1.154T16.384 21zM11.5 4H7.616q-.27 0-.443.183T7 4.616v14.769q0 .269.173.442t.443.173h8.769q.25 0 .432-.173q.183-.173.183-.442V9.673h-3.173q-.961 0-1.644-.702T11.5 7.27zm1 0v3.27q0 .578.374.99t.953.413H17v-.79L13.252 4zm-2.346 14.173q-.213 0-.357-.143q-.143-.143-.143-.357t.143-.357t.357-.143H12q.214 0 .357.143t.143.357t-.143.357t-.357.143zm0-3.788q-.213 0-.357-.144q-.143-.143-.143-.356q0-.214.143-.357q.144-.143.357-.143h3.673q.214 0 .357.143t.143.357t-.143.356t-.357.144z");
}

</style>
