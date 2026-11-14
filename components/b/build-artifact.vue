<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qq2rb_61b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:build-artifact" /></template>
<style>
.qq2rb_61b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.119 2.22q-1.118-.559-2.236 0L3.131 5.595q-.35.175-.611.405q.166.005.315.079l5.014 2.507l8.028-4.487zm4.875 2.438q.014.111-.005.221t-.07.21t-.128.181q-.078.08-.175.135L9.471 9.397l1.529.764l8.165-4.082q.148-.074.315-.079q-.261-.23-.612-.405zM7.112 9.895q.074.119.186.204q.113.084.248.123q.133.037.271.025l2.433 1.217V19.5q0 .134.046.259q.047.126.133.228q-.274-.07-.548-.207l-6.749-3.375q-1.383-.692-1.382-2.237V7.832q0-.392.088-.729q.113.211.327.318zm13.049-2.792q-.112.211-.326.318l-8.085 4.043V19.5q0 .134-.046.259q-.047.126-.133.228q.273-.07.547-.207l6.751-3.375q1.382-.692 1.381-2.237V7.832q0-.392-.089-.729");
}

</style>
