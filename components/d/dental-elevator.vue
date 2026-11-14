<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oe9u14bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dental-elevator" /></template>
<style>
.oe9u14bfh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.989 14.071l3.906-3.905q2.829-.854 4.649-2.775q2.117-2.235 1.696-4.764q-.005-.03-.012-.059q-.018-.072-.05-.138q-.031-.067-.075-.126q-.044-.06-.099-.109q-.055-.05-.118-.088t-.133-.063t-.143-.036t-.146-.007q-.074.003-.146.021q-4.428 1.107-6.472 7.072l-3.917 3.917q-.523-.279-1.162-.279q-1.035 0-1.767.733L3.465 17q-.733.732-.733 1.768q0 1.035.733 1.767q.732.733 1.767.733q1.036 0 1.768-.733L10.535 17q.733-.732.733-1.768q0-.638-.279-1.161");
}

</style>
