<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG25NHCbJu)" class="pdcehqjen"/><path fill="url(#SVGduLAPYJX)" class="l0oxbktuu"/><defs><linearGradient id="SVG25NHCbJu" x1="20.999" x2="6.575" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="krg6cobdb"/><stop offset="1" class="k035qibmw"/></linearGradient><linearGradient id="SVGduLAPYJX" x1="3.001" x2="10.888" y1="11.999" y2="11.999" gradientUnits="userSpaceOnUse"><stop class="mbca8hmpk"/><stop offset="1" class="dg58bcc7y"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dmt" /></template>
<style>
.dg58bcc7y {
  stop-color: var(--svg-color--02f8af, #02f8af);
}

.ft5dv1b6b {
  fill: none;
}

.k035qibmw {
  stop-color: var(--svg-color--009299, #009299);
}

.krg6cobdb {
  stop-color: var(--svg-color--01fbdf, #01fbdf);
}

.l0oxbktuu {
  d: path("M6.364 3h.182c-.723 0-.599.495-.542.594L8.35 7.5l2.257 3.736q.407.763 0 1.528L8.35 16.499s-1.896 3.142-2.348 3.82c0 0-.361.68.542.68h8.668h-8.848c-.091 0-.562.04-.923-.215a2.6 2.6 0 0 1-.55-.522l-1.688-2.83c-.27-.423-.27-.933 0-1.272l1.955-3.411c.11-.18.165-.495.165-.75c0-.146-.098-.437-.263-.755L3.21 7.849c-.271-.424-.271-.933 0-1.273l1.711-2.887c.148-.223.23-.337.564-.524c.282-.159.606-.165.878-.165");
}

.mbca8hmpk {
  stop-color: var(--svg-color--00bd97, #00bd97);
}

.pdcehqjen {
  d: path("M5.411 3.255Q5.808 3 6.207 3h8.844c.53 0 1.061.255 1.327.764l4.422 7.471a1.57 1.57 0 0 1 0 1.528l-4.422 7.47c-.266.51-.796.765-1.327.765H6.207q-.397 0-.796-.255c-.177-.17-.442-.34-.53-.51l-1.681-2.8c-.266-.424-.266-.934 0-1.273l1.945-3.396c.177-.255.177-.51.177-.764q0-.383-.266-.764L3.2 7.84c-.265-.424-.265-.933 0-1.273l1.68-2.802c.089-.17.266-.424.531-.51m2.742 13.158s.475.085.74.085h3.593c.53 0 1.062-.17 1.327-.68l1.857-3.055a1.57 1.57 0 0 0 0-1.528l-1.857-3.141c-.265-.51-.801-.595-1.332-.595H8.153l2.21 3.736a1.56 1.56 0 0 1 0 1.528z");
}

</style>
