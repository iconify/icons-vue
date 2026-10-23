<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5hna9c2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:brightness-auto-rounded" /></template>
<style>
.f5hna9c2h {
  fill: currentColor;
  d: path("M9.066 19h-2.45q-.667 0-1.141-.475T5 17.386v-2.451l-1.79-1.803q-.237-.243-.349-.534t-.111-.594q0-.301.112-.596t.347-.538L5 9.066v-2.45q0-.667.475-1.141T6.615 5h2.451l1.803-1.79q.243-.237.534-.349t.594-.111q.301 0 .596.112t.538.347L14.934 5h2.45q.667 0 1.142.475T19 6.615v2.451l1.79 1.803q.237.243.349.534t.111.594q0 .301-.111.596t-.348.538L19 14.934v2.45q0 .667-.475 1.142t-1.14.474h-2.451l-1.803 1.79q-.243.237-.534.349t-.594.111q-.301 0-.596-.111t-.538-.348zm1.096-5.608h3.726l.914 2.325q.056.142.171.213q.115.07.254.07q.24 0 .375-.187q.136-.188.05-.423l-3.235-8.204q-.03-.088-.108-.137Q12.229 7 12.14 7h-.237q-.096 0-.175.049q-.078.05-.108.137l-3.215 8.218q-.087.215.046.406q.133.19.382.19q.157 0 .257-.08q.101-.08.157-.209zm.296-.8l1.492-4.019h.1l1.53 4.02z");
}

</style>
