<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0k3-hbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:charger-private" /></template>
<style>
.g0k3-hbao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143L9.81 4.132q2.19-1.866 4.38 0l5.875 5.011q1.185 1.011 1.185 2.568v3.881q-.422-.362-.984-.503q-.041-1.385-1.458-2.024q-1.703-.767-2.898.668l-.001.001l-1.736 2.084q-1.098 1.323-.37 2.876q.555 1.182 1.681 1.466q-.009.616.235 1.09H6.125q-3.375 0-3.375-3.375v-6.164q0-1.557 1.185-2.568m12.935 5.39q.587-.705 1.423-.328t.697 1.285l-.022.141q-.037.244.123.432q.161.187.408.187q.925 0 1.329.832q.404.833-.169 1.56l-1.726 2.185q-.582.739-1.447.368q-.865-.372-.729-1.301l.038-.265q.035-.249-.13-.439q-.164-.19-.417-.19q-.922-.001-1.314-.836q-.391-.835.199-1.546zm-.52 2.969l1.146-1.376q.098.494.458.913q.594.693 1.499.711l-1.17 1.481q-.081-.559-.484-1.024q-.58-.669-1.449-.705");
}

</style>
