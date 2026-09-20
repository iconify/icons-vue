<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_l0hwb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:clinical-notes-outline-sharp" /></template>
<style>
.c_l0hwb7b {
  fill: currentColor;
  d: path("M15.366 14.962q-.674-.673-.674-1.635t.674-1.635T17 11.02t1.635.673q.673.674.673 1.635t-.674 1.635t-1.634.673t-1.634-.673m2.558-.711q.384-.384.384-.924t-.384-.924T17 12.02t-.924.384t-.384.924t.384.924t.924.384t.924-.384m-6.232 7.288v-3.102q.858-.504 1.775-.837t1.887-.494L17 19.25l1.627-2.144q.996.127 1.91.486q.913.36 1.77.839v3.107zm.975-1h4.056l-1.754-2.304q-.61.143-1.186.372q-.575.23-1.116.532zm4.61 0h4.03v-1.4q-.534-.308-1.11-.524t-1.186-.361zM8.923 20H4V4h16v5.308q-.227-.212-.461-.383T19 8.662V5H5v14h3.923zM7.5 8.73h7.423q.362-.21.762-.307q.4-.096.815-.134V7.73h-9zm0 3.77h4.52q.038-.275.102-.516q.065-.24.15-.484H7.5zm0 3.77h2.439l1.448-.676v-.325H7.5zM8.923 19H5V5h14v3.656q-.47-.2-.975-.303Q17.519 8.25 17 8.25q-2.107 0-3.592 1.485t-1.485 3.592q0 .497.097.954t.292.884l-3.389 1.572zM17 13.327");
}

</style>
