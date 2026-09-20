<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w6fns-ydo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:history-edu-outline" /></template>
<style>
.w6fns-ydo {
  fill: currentColor;
  d: path("M8.23 18.77q-.42 0-.71-.29t-.29-.71v-2H10v-3.25q-.952.2-1.951-.061T6.4 11.542v-1.407H4.98L2.193 7.346q.862-.784 1.956-1.173T6.4 5.785q.964 0 1.87.273t1.73.856V5.077h10v11.692q0 .847-.577 1.423T18 18.77zm2.77-3h6v1q0 .424.288.712t.712.287t.713-.287t.287-.713V6.077h-8v1.6l5.5 5.5v.708h-.708l-3.042-3.043l-.565.566q-.293.292-.575.49t-.61.348zM5.408 9.134H7.4v1.957q.512.316.952.43t.848.113q.69 0 1.249-.233t1.047-.721l.546-.546l-1.746-1.746q-.802-.802-1.798-1.203t-2.098-.4q-.73 0-1.421.19q-.69.19-1.237.494zM16 16.769H8.23v1h8.074q-.171-.205-.238-.465T16 16.769m-7.77 1v-1z");
}

</style>
