<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8mkulbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:emergency-phone-sign" /></template>
<style>
.j8mkulbch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.375 1.75h-6.75q-2.848 0-4.861 2.014T1.75 8.625v6.75q0 2.848 2.014 4.861t4.861 2.014h6.75q2.848 0 4.861-2.014t2.014-4.861v-6.75q0-2.848-2.014-4.861T15.375 1.75m-7.125 4H10q.059 0 .117.009t.113.027q.056.018.109.045q.052.026.1.061q.047.034.089.075t.076.089q.035.047.062.099t.046.108l1 3q.019.058.029.118q.009.061.009.122q0 .062-.01.122t-.031.118q-.019.058-.049.112q-.029.054-.066.103t-.082.09t-.096.076l-.927.618q.968 1.599 2.579 2.555l.856-1.027q.072-.087.167-.149q.095-.061.204-.092t.222-.029t.22.038l3 1q.056.019.108.046t.099.062t.089.076t.075.089q.035.048.061.1q.027.053.045.109q.018.055.027.113t.009.117v2q0 2.5-2.5 2.5q-4.248 0-7.124-2.876T5.75 8.25q0-2.5 2.5-2.5");
}

</style>
