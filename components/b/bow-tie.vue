<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip5b5nbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bow-tie" /></template>
<style>
.ip5b5nbcc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.378 18.148l5.849-3.412q.655.514 1.523.514h.5q.868 0 1.523-.514l5.849 3.412l.043.023q1.139.57 1.91-.008q.675-.507.675-1.663v-9q0-1.156-.675-1.662q-.771-.579-1.91-.009l-.043.023l-5.718 3.336q-.608-.438-1.654-.438h-.5q-1.046 0-1.654.438L4.378 5.852l-.043-.023q-1.139-.57-1.91.009q-.675.506-.675 1.662v9q0 1.156.675 1.663q.771.578 1.91.008zM3.643 7.16l5.679 3.313q-.072.352-.072.777v1.5q0 .4.109.755L3.643 16.84q-.29.144-.318.122q-.075-.056-.075-.462v-9q0-.406.075-.463q.028-.021.318.123m16.714 9.68l-5.716-3.335q.109-.355.109-.755v-1.5q0-.425-.072-.777l5.679-3.313q.29-.144.318-.123q.075.057.075.463v9q0 .406-.075.462q-.028.022-.318-.122");
}

</style>
