<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":218};
const content = `<path class="syqp9qb4v"/><path class="el5k8kb9n"/><path class="mzy_xmcxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:dev-icon" /></template>
<style>
.el5k8kb9n {
  d: path("M156.445 106.018c-.97-7.758-4.849-15.516-10.667-20.365L45.893 6.133c-12.607-9.698-30.062-7.758-39.76 4.849c-9.698 12.607-7.758 30.062 4.849 39.76l72.731 58.185l-72.731 58.185c-12.607 9.698-14.547 27.154-4.849 39.76c9.698 12.607 27.153 14.547 39.76 4.85l99.885-81.46c6.788-5.819 10.667-13.577 10.667-22.305v-1.94");
  fill: var(--svg-color--0d55ff, #0D55FF);
}

.mzy_xmcxk {
  d: path("M255.952 188.282c0 15.516-12.607 28.123-28.123 28.123c-15.516 0-28.123-12.607-28.123-28.123c0-15.516 12.607-28.123 28.123-28.123c15.516 0 28.123 12.607 28.123 28.123");
  fill: var(--svg-color--7000f2, #7000F2);
}

.syqp9qb4v {
  d: path("M226.859 160.16h-86.308c-.97 0-2.91 0-3.88.969l-64.973 51.397c-.97.97-.97 1.94 0 2.91c0 .97.97.97 1.94.97h154.19c15.517 0 29.093-13.578 28.124-30.063c-.97-15.516-14.547-26.184-29.093-26.184");
  fill: var(--svg-color--00c9db, #00C9DB);
}

</style>
