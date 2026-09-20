<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pb6q7sbjm"/><path class="jt3lo0heq"/><path class="fhnn8sb7j"/><path fill="url(#SVGwUF95dCU)" class="g930kjpwm"/><path class="g86d6j6vm"/><path class="txf__ibib"/><defs><linearGradient id="SVGwUF95dCU" x1="3.001" x2="21.347" y1="11.309" y2="11.309" gradientUnits="userSpaceOnUse"><stop class="k827ibcbc"/><stop offset=".2" class="w0k8ahbcl"/><stop offset=".54" class="we2yf3b-w"/><stop offset="1" class="eduq_71-i"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ben" /></template>
<style>
.eduq_71-i {
  stop-color: var(--svg-color--e95e1b, #e95e1b);
}

.fhnn8sb7j {
  fill: var(--svg-color--e2e3e9, #e2e3e9);
  d: path("M12 18.772c4.04 0 7.313-3.16 7.313-7.053S16.039 4.665 12 4.665c-4.04 0-7.313 3.161-7.313 7.054c0 3.892 3.274 7.053 7.313 7.053m0 .54c4.349 0 7.875-3.397 7.875-7.593c0-4.197-3.526-7.594-7.874-7.594c-4.349 0-7.875 3.397-7.875 7.594c0 4.196 3.526 7.593 7.875 7.593");
}

.ft5dv1b6b {
  fill: none;
}

.g86d6j6vm {
  fill: var(--svg-color--7d7f7c, #7d7f7c);
  d: path("M9.188 9.187V9h1.687v.186zm3.374 0V9h1.688v.186zm-1.687 1.996v-.275l.844.546l.844-.816v.27l-.844.821zm-1.687-1.096l-.282-.27l-.281 1.366h.281l.282-1.09zM8.063 14.45l-3.094-2.998v.276l3.206 2.998l.281-1.367l.732.276l1.687-1.091v-.276L9.188 13.36c-.225-.213-.659-.27-.844-.27zm2.812 3.443v-.27L12 18.17l1.125-.546c-.186-1.091-.281-4.264 1.969-5.08l.28.27c-1.405.496-2.474 2.408-2.249 4.81v.27L12 18.44zm7.594-6.44v-.27l-3.094 2.446v.27l3.094-2.452z");
}

.g930kjpwm {
  d: path("M12 18.75c4.039 0 7.313-3.148 7.313-7.031c0-3.884-3.274-7.031-7.312-7.031s-7.313 3.147-7.313 7.03s3.274 7.032 7.313 7.032");
}

.jt3lo0heq {
  fill: var(--svg-color--6389b0, #6389b0);
  d: path("M12 20.46c4.97 0 9-3.909 9-8.73S16.97 3 12 3s-9 3.908-9 8.73c0 4.821 4.03 8.73 9 8.73");
}

.k827ibcbc {
  stop-color: var(--svg-color--6d7ace, #6d7ace);
}

.pb6q7sbjm {
  fill: var(--svg-color--3b5169, #3b5169);
  d: path("M12 21c4.97 0 9-3.785 9-8.454s-4.03-8.454-9-8.454s-9 3.785-9 8.454S7.03 21 12 21");
}

.txf__ibib {
  fill: var(--svg-color--e3e3e3, #e3e3e3);
  d: path("M10.875 9.003v1.912l.844.54l.844-.816V9.004h1.687L11.437 5.46l-2.25 3.544zM12 18.17l-1.125-.545c-.45-4.585 2.436-6.627 3.938-6.987l-.282-1.09l3.938 1.63l-3.094 2.459l-.281-1.092c-2.025.872-2.155 3.808-1.969 5.08zm-1.125-5.9l-1.687 1.091c-.225-.214-.659-.27-.844-.27l-.281 1.361l-3.094-2.998l3.937-1.631l-.281 1.361c1.125 0 1.969.726 2.25 1.086");
}

.w0k8ahbcl {
  stop-color: var(--svg-color--9971a3, #9971a3);
}

.we2yf3b-w {
  stop-color: var(--svg-color--ca6664, #ca6664);
}

</style>
