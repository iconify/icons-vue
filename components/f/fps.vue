<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG9HetO9iE)" class="l-f1d07nm"/><path fill="url(#SVGJa0t6cgo)" class="u4hgsdkil"/><path fill="url(#SVGqY3MJcNl)" class="n7ko9mc-e"/><defs><linearGradient id="SVG9HetO9iE" x1="3.69" x2="20.623" y1="11.562" y2="11.617" gradientUnits="userSpaceOnUse"><stop class="or8levbmg"/><stop offset="1" class="h39z6w05y"/></linearGradient><linearGradient id="SVGJa0t6cgo" x1="-29.493" x2="105.377" y1=".086" y2=".709" gradientUnits="userSpaceOnUse"><stop class="or8levbmg"/><stop offset="1" class="h39z6w05y"/></linearGradient><linearGradient id="SVGqY3MJcNl" x1="3.689" x2="20.623" y1="11.563" y2="11.618" gradientUnits="userSpaceOnUse"><stop class="or8levbmg"/><stop offset="1" class="h39z6w05y"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fps" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h39z6w05y {
  stop-color: var(--svg-color--8760fb, #8760fb);
}

.l-f1d07nm {
  d: path("M11.849 9.502a1.2 1.2 0 0 1-.54-.365q-.765-.898-1.815-2.18c-.575-.704-1.26-1.404-2.22-1.454a2.945 2.945 0 0 0-3.114 2.55c-.35 2.12-.7 4.24-1.035 6.359q-.1.537-.125 1.085a2.99 2.99 0 0 0 3.02 2.99a3.015 3.015 0 0 0 2.864-2.675h-.01l-.01-.005a2.09 2.09 0 0 1-.7-4.01c.985-.42 2.07.04 2.55 1.01c.149.377.225.78.225 1.185l.015.01h1.95c.02 0 .03-.01.04-.02a.06.06 0 0 0 .02-.04c.05-1.135.785-2.28 1.95-2.315a2.02 2.02 0 0 1 1.845 1.17c.59 1.3-.2 2.83-1.605 2.985c-.035 0-.05.025-.05.06c.255 1.665 1.65 2.86 3.314 2.634a3.01 3.01 0 0 0 2.502-2.287a3 3 0 0 0 .038-1.192c-.32-2.05-.7-4.395-1.14-7.024a2.94 2.94 0 0 0-3.175-2.45c-.924.075-1.694.86-2.26 1.555l-.424.525q-.62.788-1.28 1.544c-.215.24-.49.42-.825.36z");
}

.n7ko9mc-e {
  d: path("M16.099 13.683a1.15 1.15 0 0 1-1.13 1.16a1.15 1.15 0 0 1-1.13-1.16a1.15 1.15 0 0 1 1.13-1.155a1.15 1.15 0 0 1 1.13 1.154");
}

.or8levbmg {
  stop-color: var(--svg-color--aa32f2, #aa32f2);
}

.u4hgsdkil {
  d: path("M8.899 14.847a1.15 1.15 0 0 0 1.13-1.16a1.15 1.15 0 0 0-1.13-1.16a1.145 1.145 0 0 0-1.13 1.16a1.146 1.146 0 0 0 1.13 1.16");
}

</style>
