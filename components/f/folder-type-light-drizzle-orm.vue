<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mv897jbch"/><path class="yh9tl8d4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-drizzle-orm" /></template>
<style>
.mv897jbch {
  fill: var(--svg-color--3e3e3e, #3e3e3e);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21zm0 4.2h-8.2l1.1-2.1h7.1z");
}

.yh9tl8d4p {
  d: path("M14.34 24.12a.919.909-15.81 0 1 .34 1.24l-2.96 5.17a.916.906-15.81 0 1-1.25.34a.921.911-15.81 0 1-.35-1.24l2.96-5.16a.925.915-15.81 0 1 1.26-.35m6.38-3.96a.919.909-15.81 0 1 .34 1.24l-2.96 5.17a.916.906-15.81 0 1-1.25.34a.921.911-15.81 0 1-.35-1.24l2.96-5.16a.925.915-15.81 0 1 1.26-.35m9.81 0a.921.911-15.81 0 1 .35 1.24l-2.96 5.17a.923.913-15.81 0 1-1.26.34a.919.909-15.81 0 1-.34-1.24l2.96-5.16a.918.908-15.81 0 1 1.25-.35m-6.38 3.96a.921.911-15.81 0 1 .35 1.24l-2.96 5.17a.923.913-15.81 0 1-1.26.34a.919.909-15.81 0 1-.34-1.24l2.95-5.16a.925.915-15.81 0 1 1.26-.35");
}

</style>
