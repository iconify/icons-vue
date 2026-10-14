<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ia_jvxbqb"/><path class="yh9tl8d4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-drizzle-orm-opened" /></template>
<style>
.ia_jvxbqb {
  fill: var(--svg-color--585858, #585858);
  d: path("M29.5 5.5H18.2l-2.1 4.2H4.3v16.8h25.2zm-2.1 18.7H6.6V11.8h20.8zm0-14.5h-8.2l1-2.1h7.1zm-1.7 4H.5l3.8 12.8h25.2z");
}

.yh9tl8d4p {
  d: path("M14.34 24.12a.919.909-15.81 0 1 .34 1.24l-2.96 5.17a.916.906-15.81 0 1-1.25.34a.921.911-15.81 0 1-.35-1.24l2.96-5.16a.925.915-15.81 0 1 1.26-.35m6.38-3.96a.919.909-15.81 0 1 .34 1.24l-2.96 5.17a.916.906-15.81 0 1-1.25.34a.921.911-15.81 0 1-.35-1.24l2.96-5.16a.925.915-15.81 0 1 1.26-.35m9.81 0a.921.911-15.81 0 1 .35 1.24l-2.96 5.17a.923.913-15.81 0 1-1.26.34a.919.909-15.81 0 1-.34-1.24l2.96-5.16a.918.908-15.81 0 1 1.25-.35m-6.38 3.96a.921.911-15.81 0 1 .35 1.24l-2.96 5.17a.923.913-15.81 0 1-1.26.34a.919.909-15.81 0 1-.34-1.24l2.95-5.16a.925.915-15.81 0 1 1.26-.35");
}

</style>
