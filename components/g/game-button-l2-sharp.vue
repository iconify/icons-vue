<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4w9ldb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:game-button-l2-sharp" /></template>
<style>
.a4w9ldb_t {
  fill: currentColor;
  d: path("M3 19V8.27q0-1.362.973-2.326q.973-.963 2.354-.963h11.346q1.38 0 2.354.963Q21 6.908 21 8.27V19zm9.483-3.823h4.169v-.84h-3.064v-.056l1.34-1.202q.807-.742 1.146-1.31t.34-1.219q0-.802-.526-1.264t-1.402-.463q-.578 0-1.063.251q-.484.251-.892.745l.54.508q.371-.388.682-.537q.31-.148.722-.148q.483 0 .777.266q.294.265.294.704q0 .501-.279.938t-1.038 1.19l-1.746 1.664zm-5.18 0h3.803v-.827H8.159V8.966h-.855z");
}

</style>
