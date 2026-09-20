<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p_y-qqblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:group" /></template>
<style>
.p_y-qqblv {
  fill: currentColor;
  d: path("M2.596 18.616v-1.647q0-.696.36-1.197q.361-.5.971-.799q1.3-.621 2.583-.99q1.282-.367 3.086-.367t3.087.368t2.583.989q.609.298.97.799q.36.501.36 1.197v1.647zm16 0v-1.693q0-.87-.353-1.641q-.352-.772-.997-1.324q.737.15 1.42.416q.682.267 1.35.599q.65.327 1.019.834t.369 1.116v1.693zM7.473 10.508q-.877-.877-.877-2.123t.877-2.123t2.123-.877t2.123.877t.877 2.123t-.877 2.123t-2.123.877t-2.123-.877m8.516 0q-.877.877-2.123.877q-.064 0-.162-.015t-.162-.031q.502-.628.778-1.381q.276-.754.276-1.573q0-.82-.285-1.564q-.286-.744-.769-1.39q.081-.029.162-.038t.162-.008q1.246 0 2.123.877t.877 2.123t-.877 2.123");
}

</style>
