<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGU8UcId9i)" class="kt5bvpb6c"/><path fill="url(#SVGb6Ra9dKH)" class="hjzo01b0b"/><defs><linearGradient id="SVGU8UcId9i" x1="6.858" x2="16.998" y1="5.893" y2="19.13" gradientUnits="userSpaceOnUse"><stop class="z0ej23bum"/><stop offset=".24" class="recmq4bct"/><stop offset=".37" class="dd0_o-_2i"/><stop offset=".45" class="t97btubzk"/><stop offset=".53" class="eoxw9sb-t"/><stop offset=".8" class="cysuggbsy"/><stop offset=".97" class="j2ro9pbvg"/></linearGradient><linearGradient id="SVGb6Ra9dKH" x1="6.857" x2="16.997" y1="5.894" y2="19.131" gradientUnits="userSpaceOnUse"><stop class="z0ej23bum"/><stop offset=".24" class="recmq4bct"/><stop offset=".37" class="dd0_o-_2i"/><stop offset=".45" class="t97btubzk"/><stop offset=".53" class="eoxw9sb-t"/><stop offset=".8" class="cysuggbsy"/><stop offset=".97" class="j2ro9pbvg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apefi" /></template>
<style>
.cysuggbsy {
  stop-color: var(--svg-color--e7d9be, #e7d9be);
}

.dd0_o-_2i {
  stop-color: var(--svg-color--a99367, #a99367);
}

.eoxw9sb-t {
  stop-color: var(--svg-color--b8a070, #b8a070);
}

.ft5dv1b6b {
  fill: none;
}

.hjzo01b0b {
  d: path("M8.558 7.236c.106-.106.492-.355.747-.355c.259 0 .47.25.577.355zM7.06 6.881c-.26 0-.355.25-.355.355H7.5c0-.106-.185-.355-.439-.355m.704.884c-.254 0-.53-.132-.53-.238l1.06-.026c0 .106-.276.264-.53.264");
}

.j2ro9pbvg {
  stop-color: var(--svg-color--d7c6a1, #d7c6a1);
}

.kt5bvpb6c {
  d: path("M9.004 20.934c.238-1.921.985-6.193 2.229-9.21c-.858.974-2.568 3.366-2.568 5.177c-.423-.757-1.35-2.652-1.604-4.203c-.317.968-.582 3.361.964 5.171l-.64 2.584l-3.855-2.26c.212-.324.64-1.033.64-1.292c0-.323-.317-.646-.64-.323c.106-.757.64-2.589 1.927-3.88V9.14c0-.317.127-1.032.64-1.291c.514-.26 1.499.54 1.928.969c-.212-.106-.773-.318-1.287-.318s-.64.212-.64.318c.106.54.513 1.614 1.286 1.614c.768 0 1.604-.857 1.922-1.292c0-.354-.191-1.048-.964-.968c.106-.106.387-.323.646-.323c.254 0 .963.212 1.281.323c.106-.106.318-.45.318-.969c0-.646-.318-1.292-.959-1.292c-.375 0-.751.329-1.058.604c-.228.196-.413.365-.545.365c-.26 0-.752-.434-.964-.646C7.701 5.154 9.242 3 10.27 3c.73 0 1.461 1.048 2.133 2.012c.509.725.985 1.402 1.398 1.545c-.53.106-1.668.583-1.927 1.615c.323-.323 1.16-.969 1.927-.969c.963 0 3.208 1.292 3.208 2.26c0 .969.323 1.943 1.286 2.589c.503.339 1.403.693 2.176.963a10.76 10.76 0 0 1-4.743 6.405v-3.165c-.318.106-1.09.969-1.604 3.552l-.117.476a10.56 10.56 0 0 1-5.002.651");
}

.recmq4bct {
  stop-color: var(--svg-color--cebc95, #cebc95);
}

.t97btubzk {
  stop-color: var(--svg-color--ae976a, #ae976a);
}

.z0ej23bum {
  stop-color: var(--svg-color--eae3d2, #eae3d2);
}

</style>
