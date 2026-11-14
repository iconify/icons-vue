<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3p9w4pqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:advisor-chat" /></template>
<style>
.m3p9w4pqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 6q0-3.25 3.25-3.25h11q3.25 0 3.25 3.25v8q0 3.25-3.25 3.25h-6.218l-3.788 3.314q-.112.099-.254.146q-.141.048-.29.038t-.282-.076q-.134-.066-.232-.178q-.09-.103-.138-.23q-.048-.128-.048-.264v-2.755q-3-.123-3-3.245zM12 5Q9.25 5 9.25 7.75q0 2.084 1.58 2.589q-2.664.439-3.071 3.045q-.011.073-.008.147t.02.146t.049.138q.031.067.074.127q.044.06.098.11t.117.088t.133.064t.142.037q.073.011.147.008t.146-.02t.138-.049t.127-.074q.06-.044.11-.098t.088-.117t.064-.133t.037-.142Q9.533 11.75 12 11.75t2.759 1.866q.011.073.037.142t.064.133t.088.117t.11.098q.06.043.127.074q.067.032.138.049t.146.02t.147-.008q.147-.023.275-.101q.127-.077.215-.198q.088-.12.123-.265t.012-.293q-.407-2.606-3.071-3.045q1.58-.505 1.58-2.589Q14.75 5 12 5");
}

</style>
