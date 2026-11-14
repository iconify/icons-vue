<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yguitacth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exercise-demo" /></template>
<style>
.yguitacth {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v6q0 1.76-1.245 3.005T18 17.25h-3.039l.767 3.068q.022.09.022.182q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.092 0-.182-.022q-.072-.018-.138-.05q-.067-.031-.126-.075q-.06-.044-.109-.099q-.05-.055-.088-.118t-.063-.133t-.036-.143t-.007-.146q.003-.074.021-.146l.767-3.068H6q-1.76 0-3.005-1.245T1.75 13V7q0-1.76 1.245-3.005T6 2.75m4.586 14.5l-.625 2.5h4.078l-.625-2.5zm3.55-9.233l-2.324-1.245q-1.124-.602-2.218.053T8.5 8.755v2.49q0 1.275 1.094 1.93t2.218.053l2.324-1.245q1.187-.636 1.187-1.983t-1.187-1.983");
}

</style>
